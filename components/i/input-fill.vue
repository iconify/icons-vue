<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p51hcieek.css';
import '../../css/p/p680kacjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p51hcieek"/><path class="p680kacjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:input-fill" /></template>
