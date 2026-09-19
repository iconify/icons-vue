<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-kbjab1h.css';
import '../../css/a/ao1_d-37i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-kbjab1h"/><path class="ao1_d-37i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:face-alt-3-filled" /></template>
