<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3s9lacyv.css';
import '../../css/n/n4qa2bbyo.css';
import '../../css/b/bh5tjhb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="l3s9lacyv"/><circle class="n4qa2bbyo"/><circle class="bh5tjhb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:julia" /></template>
