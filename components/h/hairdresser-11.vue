<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riuiy0bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="riuiy0bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hairdresser-11" /></template>
