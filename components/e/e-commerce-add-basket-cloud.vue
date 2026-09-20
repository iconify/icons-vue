<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rbpmfzz7c.css';
import '../../css/m/mryjlfbzm.css';
import '../../css/d/dj2e535im.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rbpmfzz7c"/><path class="mryjlfbzm"/><path class="dj2e535im"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:e-commerce-add-basket-cloud" /></template>
