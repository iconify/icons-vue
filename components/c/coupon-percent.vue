<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l1w39n6pb.css';
import '../../css/c/c3ezjvbfd.css';
import '../../css/b/bl8r-g21u.css';
import '../../css/h/h0t1mbbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l1w39n6pb"/><path class="c3ezjvbfd"/><path class="bl8r-g21u"/><path class="h0t1mbbhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:coupon-percent" /></template>
