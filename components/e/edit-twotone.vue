<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bramihlnm.css';
import '../../css/w/wpxuws29w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bramihlnm"/><path class="wpxuws29w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:edit-twotone" /></template>
