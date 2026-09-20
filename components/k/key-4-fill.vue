<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7mumeb-d.css';
import '../../css/u/uri7qm5ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m7mumeb-d"/><path class="uri7qm5ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:key-4-fill" /></template>
