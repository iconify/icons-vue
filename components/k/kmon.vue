<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awy6hv8rm.css';
import '../../css/x/xxg6e85ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awy6hv8rm"/><path class="xxg6e85ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kmon" /></template>
