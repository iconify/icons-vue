<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np8ilvg5i.css';
import '../../css/s/s9zx-k-iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="np8ilvg5i"/><path class="s9zx-k-iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:gift-twotone" /></template>
