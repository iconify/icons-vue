<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1utpacju.css';
import '../../css/q/qeh8d-bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1utpacju"/><path class="qeh8d-bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bookmark" /></template>
