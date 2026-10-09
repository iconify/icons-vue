<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0ni6vb5b.css';
import '../../css/t/tyv6bwbtz.css';
import '../../css/a/ag5d8ub9y.css';
import '../../css/i/ijbr7jekk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="tyv6bwbtz"/><path class="ag5d8ub9y"/><path class="ijbr7jekk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:lever-20" /></template>
