<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk_85gb6j.css';
import '../../css/c/czwlbs76f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_85gb6j"/><path class="czwlbs76f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:loading-3-fill" /></template>
