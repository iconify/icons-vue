<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9ywuf_1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="v9ywuf_1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:label-hogwarts" /></template>
