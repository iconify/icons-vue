<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmb21zcef.css';
import '../../css/a/aw0qt-2do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gmb21zcef"/><path class="aw0qt-2do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-horizontal-48" /></template>
