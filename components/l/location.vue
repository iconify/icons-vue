<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v89fl4bla.css';
import '../../css/o/o4cgy6nli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="v89fl4bla"/><path class="o4cgy6nli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:location" /></template>
