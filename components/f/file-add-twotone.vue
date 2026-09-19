<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7mk-dp-h.css';
import '../../css/j/jso3jy2en.css';
import '../../css/n/n5rxf3buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t7mk-dp-h"/><path class="jso3jy2en"/><path class="n5rxf3buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-add-twotone" /></template>
