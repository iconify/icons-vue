<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/j/ji8mks.css';
import '../../css/w/wcbo4y.css';
import '../../css/a/aqo_mf.css';
import '../../css/j/jsh6kw.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ji8mks"/><path class="a0m25c wcbo4y"/><path class="a0m25c aqo_mf"/><path class="a0m25c jsh6kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:account-alert" /></template>
