<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd4yffbrl.css';
import '../../css/g/gex21tb2f.css';
import '../../css/j/jyfi0eawb.css';
import '../../css/w/wii29dbas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nd4yffbrl"/><path class="gex21tb2f"/><path class="jyfi0eawb"/><path class="wii29dbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-plus-48-bold" /></template>
