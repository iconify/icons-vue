<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x49svmbsw.css';
import '../../css/d/d510u6bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x49svmbsw"/><path class="d510u6bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:combobox" /></template>
