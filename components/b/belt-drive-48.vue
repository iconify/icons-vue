<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pouv5lbnl.css';
import '../../css/q/qqjnhll6v.css';
import '../../css/e/efnr8lb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pouv5lbnl"/><path class="qqjnhll6v"/><path class="efnr8lb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:belt-drive-48" /></template>
