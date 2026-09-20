<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghriwj-wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghriwj-wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fastmail-light" /></template>
