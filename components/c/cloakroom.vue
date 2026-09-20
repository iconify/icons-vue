<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jn9qti3en.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="jn9qti3en"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:cloakroom" /></template>
