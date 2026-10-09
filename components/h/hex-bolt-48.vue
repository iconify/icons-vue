<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdykscxue.css';
import '../../css/s/sm0cfybmw.css';
import '../../css/e/euxfqgbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gdykscxue"/><path class="sm0cfybmw"/><path class="euxfqgbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hex-bolt-48" /></template>
