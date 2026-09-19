<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acpxm6b7v.css';
import '../../css/t/tvz2u-b5t.css';
import '../../css/q/qte40pcjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="acpxm6b7v"/><path class="tvz2u-b5t"/><path class="qte40pcjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:emc2" /></template>
