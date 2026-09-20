<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsk1vyb8u.css';
import '../../css/z/zpm02gbpx.css';
import '../../css/a/am34frbkn.css';
import '../../css/b/b9qb62bje.css';
import '../../css/n/nq4h-9b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tsk1vyb8u"/><path class="zpm02gbpx"/><path class="am34frbkn"/><path class="b9qb62bje"/><path class="nq4h-9b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:herb" /></template>
