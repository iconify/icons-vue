<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzccu8bfu.css';
import '../../css/o/om3uz4b8p.css';
import '../../css/c/csyesnsto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="jzccu8bfu"/><path class="om3uz4b8p"/><path class="csyesnsto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-virtual-server-classic" /></template>
