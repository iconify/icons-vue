<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoa0fbuwz.css';
import '../../css/o/o7khdv3bk.css';
import '../../css/h/hr3wh0b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoa0fbuwz"/><circle class="o7khdv3bk"/><path class="hr3wh0b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-info" /></template>
