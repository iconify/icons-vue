<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avqxqmkpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avqxqmkpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:daikin" /></template>
