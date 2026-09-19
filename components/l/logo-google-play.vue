<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_-jwob6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b_-jwob6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-google-play" /></template>
