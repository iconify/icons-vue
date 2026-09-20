<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi5syqv6f.css';
import '../../css/y/ynooprbfx.css';
import '../../css/d/dhmi6ubno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi5syqv6f"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="dhmi6ubno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar" /></template>
