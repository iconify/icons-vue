<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abm5005hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abm5005hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:beer-fill-round" /></template>
