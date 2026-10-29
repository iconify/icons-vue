<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8nd4gbbc.css';
import '../../css/m/m9thc4yei.css';
import '../../css/j/j_-m04xen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8nd4gbbc"/><path class="m9thc4yei"/><path class="j_-m04xen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:folder" /></template>
