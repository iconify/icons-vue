<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic7c4od3i.css';
import '../../css/a/aciwzxbfa.css';
import '../../css/q/qya8mr1nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ic7c4od3i"/><path class="aciwzxbfa"/><path class="qya8mr1nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fireplace-20" /></template>
