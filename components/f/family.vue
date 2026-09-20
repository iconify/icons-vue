<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxz9yh_wd.css';
import '../../css/w/why-rnbnl.css';
import '../../css/i/i112c1ruk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xxz9yh_wd"/><path class="why-rnbnl"/><path class="i112c1ruk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:family" /></template>
