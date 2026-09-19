<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6qv5xbnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":512};
const content = `<path class="b6qv5xbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:barrel" /></template>
