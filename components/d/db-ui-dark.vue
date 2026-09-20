<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a98mh80fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a98mh80fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:db-ui-dark" /></template>
