<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84vznkgo.css';
import '../../css/f/fb3944y_s.css';
import '../../css/a/a1bg4hbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><circle class="fb3944y_s"/><circle class="a1bg4hbvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:disc-outline" /></template>
