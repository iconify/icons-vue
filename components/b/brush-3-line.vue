<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg4uyqbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg4uyqbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brush-3-line" /></template>
