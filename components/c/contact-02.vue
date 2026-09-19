<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vzmo0wbuc.css';
import '../../css/c/cene_fbuj.css';
import '../../css/j/j9d1q1wok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vzmo0wbuc"/><path class="cene_fbuj"/><path class="j9d1q1wok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:contact-02" /></template>
