<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu1ccvu1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wu1ccvu1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:horse-riding-15" /></template>
