<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vm8kr_b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vm8kr_b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:discourse-light" /></template>
