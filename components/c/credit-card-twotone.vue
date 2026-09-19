<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knaeq35ob.css';
import '../../css/p/p9-axprhp.css';
import '../../css/y/ynji0ebgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="knaeq35ob"/><path class="p9-axprhp"/><path class="ynji0ebgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:credit-card-twotone" /></template>
