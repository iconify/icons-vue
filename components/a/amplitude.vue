<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btxwembdd.css';
import '../../css/x/xx9h8gkna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":5000,"height":1000};
const content = `<path class="btxwembdd"/><path class="xx9h8gkna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:amplitude" /></template>
