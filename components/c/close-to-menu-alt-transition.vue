<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/b/bu0ohj.css';
import '../../css/l/l3-heb.css';
import '../../css/d/d-wzkz9p.css';
import '../../css/d/d-szjhyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c bu0ohj"/><path class="a0m25c l3-heb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:close-to-menu-alt-transition" /></template>
