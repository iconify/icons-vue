<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzx24fbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzx24fbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-fill" /></template>
