<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac5rqkw9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ac5rqkw9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:egg-sharp" /></template>
