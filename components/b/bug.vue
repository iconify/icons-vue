<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btkr68j8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="btkr68j8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:bug" /></template>
