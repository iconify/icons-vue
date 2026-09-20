<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to656dbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to656dbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-t-octagon-solid" /></template>
