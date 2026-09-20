<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2m8xnber.css';
import '../../css/f/f05ck7rgt.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="c2m8xnber"/><circle class="f05ck7rgt"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:intersex" /></template>
