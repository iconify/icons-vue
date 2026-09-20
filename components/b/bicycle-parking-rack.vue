<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh3ic1lnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vh3ic1lnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:bicycle-parking-rack" /></template>
