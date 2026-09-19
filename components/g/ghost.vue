<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq_ua2hba.css';
import '../../css/l/l7pgvx7mc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kq_ua2hba"/><path class="l7pgvx7mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ghost" /></template>
