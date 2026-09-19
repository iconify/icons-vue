<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuxa2bb1c.css';
import '../../css/e/ex1_iqkbv.css';
import '../../css/s/sibyveg8p.css';
import '../../css/n/nzylh7bdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="uuxa2bb1c"/><path clip-rule="evenodd" class="ex1_iqkbv"/><path clip-rule="evenodd" class="sibyveg8p"/><path clip-rule="evenodd" class="nzylh7bdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:macbook" /></template>
