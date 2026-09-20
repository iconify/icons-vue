<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bee52pb2u.css';
import '../../css/y/yl1bn7evw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="bee52pb2u"/><path class="yl1bn7evw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:add-1d" /></template>
