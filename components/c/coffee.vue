<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/n/nh6wfl.css';
import '../../css/y/ywbs5z.css';
import '../../css/r/rakmch.css';
import '../../css/s/so-to-0.css';
import '../../css/s/so-from-10.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c nh6wfl"/><path class="a0m25c ywbs5z"/><path class="a0m25c rakmch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:coffee" /></template>
