<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oanyu-b7f.css';
import '../../css/a/aq7lsdb9w.css';
import '../../css/m/mbsy57b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oanyu-b7f"/><path class="aq7lsdb9w"/><path class="mbsy57b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:assembly-line-48-bold" /></template>
