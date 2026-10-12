<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_ia6bco.css';
import '../../css/h/h3hh3dbwv.css';
import '../../css/i/i7t9jgzrw.css';
import '../../css/x/xwdhawfba.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yl_ia6bco"/><path class="h3hh3dbwv"/><path class="i7t9jgzrw"/><path class="xwdhawfba"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:key-plus-20-bold" /></template>
