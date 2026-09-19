<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wiib7gvxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="wiib7gvxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:check-square" /></template>
