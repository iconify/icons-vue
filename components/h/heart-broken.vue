<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmqvsv63l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lmqvsv63l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:heart-broken" /></template>
