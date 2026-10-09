<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfi4ayb5u.css';
import '../../css/l/ljp18512i.css';
import '../../css/e/eqwghdb8t.css';
import '../../css/p/pdcho1m7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kfi4ayb5u"/><path class="ljp18512i"/><path class="eqwghdb8t"/><path class="pdcho1m7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:coral-20" /></template>
