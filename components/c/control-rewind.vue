<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5lvhug6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w5lvhug6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:control-rewind" /></template>
