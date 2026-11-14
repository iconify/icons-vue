<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_g-zhmcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-alt" /></template>
<style>
.p_g-zhmcy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.017 10.926l9.5-8q.05-.042.107-.075t.119-.056t.126-.034T12 2.75t.131.011t.126.034t.119.056t.107.075l9.5 8q.114.096.183.229q.069.132.081.281q.013.149-.032.291t-.141.256t-.229.183q-.132.069-.281.081q-.149.013-.291-.032t-.256-.141l-1.267-1.067V19q0 1.75-1.75 1.75H6q-1.75 0-1.75-1.75v-7.993l-1.267 1.067q-.114.096-.256.141t-.291.032t-.281-.081q-.133-.069-.229-.183q-.047-.056-.083-.121t-.058-.135q-.022-.071-.03-.144t-.002-.147t.027-.145t.054-.136t.08-.123t.103-.106M12.75 19.25V15q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 14.25t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v4.25H6q-.25 0-.25-.25V9.744L12 4.481l6.25 5.263V19q0 .25-.25.25z");
}

</style>
