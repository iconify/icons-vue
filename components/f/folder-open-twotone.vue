<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbx5wd37y.css';
import '../../css/u/u9ewtabjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bbx5wd37y"/><path class="u9ewtabjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:folder-open-twotone" /></template>
