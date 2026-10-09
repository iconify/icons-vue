<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c56z29arz.css';
import '../../css/d/dj9nk1b3p.css';
import '../../css/h/hgry93bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c56z29arz"/><path class="dj9nk1b3p"/><path class="hgry93bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lay-vessel-20-bold" /></template>
