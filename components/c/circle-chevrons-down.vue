<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kulatpbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kulatpbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-chevrons-down" /></template>
