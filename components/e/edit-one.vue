<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/t/ty_00eb4z.css';
import '../../css/v/vssgzbhpi.css';
import '../../css/c/ccljrla5i.css';
import '../../css/o/otqf1nyzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="ty_00eb4z"/><path class="vssgzbhpi"/><path class="ccljrla5i"/><path class="otqf1nyzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:edit-one" /></template>
