<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q63--4k9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q63--4k9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:caret-up" /></template>
