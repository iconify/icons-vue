<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bztp34bnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bztp34bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:clojure" /></template>
