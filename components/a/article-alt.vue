<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxd-8e_9n.css';
import '../../css/t/tlplblg9a.css';
import '../../css/h/hse9jrbcs.css';
import '../../css/u/ucf26ob4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxd-8e_9n"/><path class="tlplblg9a"/><path clip-rule="evenodd" class="hse9jrbcs"/><path class="ucf26ob4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-alt" /></template>
