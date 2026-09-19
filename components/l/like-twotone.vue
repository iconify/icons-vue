<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_esyy1fg.css';
import '../../css/q/q542tnbix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e_esyy1fg"/><path class="q542tnbix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:like-twotone" /></template>
