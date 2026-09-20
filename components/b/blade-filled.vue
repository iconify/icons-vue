<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw063kx1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sw063kx1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blade-filled" /></template>
