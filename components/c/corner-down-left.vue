<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyfjpwsme.css';
import '../../css/d/d_33tyskh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyfjpwsme wm-k"/><path class="d_33tyskh wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:corner-down-left" /></template>
