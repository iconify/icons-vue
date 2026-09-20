<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfa8fdc7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kfa8fdc7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:call-in" /></template>
