<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx0-wbbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-document" /></template>
<style>
.bx0-wbbcp {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v11.885q0 .69-.462 1.153T17.384 21zm1.346-2.77h8.077q-.081-.993-.597-1.816q-.515-.824-1.373-1.308l.758-1.373q.05-.081.015-.177q-.034-.096-.12-.146q-.082-.05-.165-.026t-.134.106l-.783 1.404q-.384-.161-.798-.245q-.413-.083-.842-.083t-.833.083t-.808.245l-.782-1.404q-.05-.086-.143-.106q-.094-.019-.18.031q-.02 0-.081.318l.777 1.373q-.858.485-1.383 1.308t-.605 1.817m1.948-1.333q-.121-.121-.121-.283t.12-.282t.283-.121t.274.12t.111.284t-.111.282t-.274.121t-.282-.121m3.634 0q-.121-.121-.121-.283t.121-.282t.283-.121t.273.12t.112.284t-.112.282t-.273.121t-.283-.121M14 8h4l-4-4z");
}

</style>
