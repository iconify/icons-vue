<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n28sx5w0p.css';
import '../../css/h/h81cxxbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n28sx5w0p"/><path class="h81cxxbry ouiIcon__fillSecondary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-workplace-search" /></template>
