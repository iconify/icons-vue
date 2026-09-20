<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcf9lrb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fcf9lrb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dice-d20-solid" /></template>
