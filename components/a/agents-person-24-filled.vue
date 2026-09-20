<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh-ufj-ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:agents-person-24-filled" /></template>
<style>
.rh-ufj-ru {
  fill: currentColor;
  d: path("M20.228 17c.978 0 1.772.793 1.772 1.773v.102C22 20.431 20.714 22 17.5 22S13 20.437 13 18.875v-.102c0-.98.794-1.773 1.772-1.773zm-7.58-14c-.293.37-.525.796-.674 1.265l-.356 1.12h.017L7.508 18.384c-.15.475-.017.965.468 1.08a.67.67 0 0 0 .5-.088a.95.95 0 0 0 .435-.537l4.492-14.12a2.47 2.47 0 0 1 3.563-1.402l.025.014c.37.213.683.523.904.905l3.823 6.641c.4.695.4 1.551 0 2.246l-.976 1.693A3.5 3.5 0 0 0 17.5 10h-.002c-1.507 0-2.853.954-3.372 2.29l2.108-6.67c.155-.491.02-.997-.478-1.12s-.795.273-.923.675L10.34 19.294a2.45 2.45 0 0 1-3.56 1.376l-.023-.014a2.45 2.45 0 0 1-.9-.933l-3.615-6.626a2.25 2.25 0 0 1 .026-2.2l3.897-6.771q.118-.205.272-.376h-.012A2.25 2.25 0 0 1 8.104 3zm4.852 8a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

</style>
