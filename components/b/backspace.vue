<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo7j_okwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bo7j_okwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:backspace" /></template>
