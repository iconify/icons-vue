<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4lvfq02u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w4lvfq02u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:jabber" /></template>
