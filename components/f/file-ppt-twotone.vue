<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu3ocmbje.css';
import '../../css/e/eq_93_56q.css';
import '../../css/j/jso3jy2en.css';
import '../../css/a/a7at0s-6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xu3ocmbje"/><path class="eq_93_56q"/><path class="jso3jy2en"/><path class="a7at0s-6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:file-ppt-twotone" /></template>
