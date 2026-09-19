<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b89uwe67v.css';
import '../../css/r/rdyolcbjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b89uwe67v"/><path class="rdyolcbjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:alert-twotone" /></template>
