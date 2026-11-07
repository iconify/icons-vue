<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/n/n74totb4p.css';
import '../../css/c/cdl9xjyfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="n74totb4p"/><path clip-rule="evenodd" class="cdl9xjyfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:high-definition-bold-duotone" /></template>
