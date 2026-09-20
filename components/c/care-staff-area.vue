<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae6uv7dgk.css';
import '../../css/b/bkulhccha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ae6uv7dgk"/><path class="bkulhccha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:care-staff-area" /></template>
