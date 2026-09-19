<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9-buhbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="h9-buhbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lifehacker" /></template>
