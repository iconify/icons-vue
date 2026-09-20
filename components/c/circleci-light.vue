<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtat2y9dp.css';
import '../../css/f/f29qyf3ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="jtat2y9dp"/><path class="f29qyf3ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:circleci-light" /></template>
