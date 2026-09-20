<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc6y9objc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc6y9objc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:football" /></template>
