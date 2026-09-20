<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a_wi43-5u.css';
import '../../css/i/i4y7lm7jg.css';
import '../../css/c/co8929bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a_wi43-5u"/><path class="i4y7lm7jg"/><path class="co8929bxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:coin-b" /></template>
