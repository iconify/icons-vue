<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8-4tb2b.css';
import '../../css/z/z9c104box.css';
import '../../css/y/yyn-_s14g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gc8-4tb2b"/><path class="z9c104box"/><path class="yyn-_s14g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:calculator-twotone" /></template>
