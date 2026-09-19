<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1a8a243t.css';
import '../../css/f/fkfwtja1r.css';
import '../../css/n/niz7j71ie.css';
import '../../css/t/txvtnaccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o1a8a243t"/><circle class="fkfwtja1r"/><path class="niz7j71ie"/><path class="txvtnaccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-volume-alt" /></template>
