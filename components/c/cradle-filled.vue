<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbpd1jbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbpd1jbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cradle-filled" /></template>
