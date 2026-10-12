<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn3tamb9f.css';
import '../../css/a/a9b7zrdqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vn3tamb9f"/><path class="a9b7zrdqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:inbox-fill-20" /></template>
