<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqfy24bla.css';
import '../../css/i/ijmbz5bch.css';
import '../../css/u/u1ktodbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aqfy24bla"/><path class="ijmbz5bch"/><path class="u1ktodbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:drag" /></template>
