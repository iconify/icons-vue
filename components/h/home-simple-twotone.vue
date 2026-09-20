<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7wwud.css';
import '../../css/a/a0m25c.css';
import '../../css/o/oq600w.css';
import '../../css/s/sdwher.css';
import '../../css/o/odxlyn.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7wwud"/><path class="a0m25c oq600w"/><path class="a0m25c sdwher"/><path class="a0m25c odxlyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:home-simple-twotone" /></template>
