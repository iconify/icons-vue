<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo_2v9b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path clip-rule="evenodd" class="bo_2v9b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:android-os" /></template>
