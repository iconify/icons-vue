<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdwcq3bta.css';
import '../../css/s/s865abbii.css';
import '../../css/a/ame6s9x0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bdwcq3bta"/><path class="s865abbii"/><path class="ame6s9x0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flask-48" /></template>
