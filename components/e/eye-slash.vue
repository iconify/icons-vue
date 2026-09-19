<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mni_8lbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mni_8lbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:eye-slash" /></template>
