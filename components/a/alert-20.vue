<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbybcrbbp.css';
import '../../css/o/olr0j3b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bbybcrbbp"/><path class="olr0j3b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:alert-20" /></template>
