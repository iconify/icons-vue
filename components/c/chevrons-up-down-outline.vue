<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftg7u_q6r.css';
import '../../css/c/ce_1shb3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftg7u_q6r"/><path class="ce_1shb3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-up-down-outline" /></template>
