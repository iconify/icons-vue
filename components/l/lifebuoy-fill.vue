<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0y2rbkof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0y2rbkof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lifebuoy-fill" /></template>
