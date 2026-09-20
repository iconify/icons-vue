<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idz8dpb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="idz8dpb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:appointments-solid" /></template>
