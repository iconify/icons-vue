<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvfqrdebp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nvfqrdebp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:castle-with-battlements-and-turret" /></template>
