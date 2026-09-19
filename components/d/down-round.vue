<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bifzlh2iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bifzlh2iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:down-round" /></template>
