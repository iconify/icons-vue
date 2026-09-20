<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0q8ttbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apk-install" /></template>
<style>
.o0q8ttbup {
  fill: currentColor;
  d: path("m18.539 21l-3.289-3.308l.689-.713l2.1 2.094v-4.861h1v4.861l2.1-2.075l.688.694zM4.615 21q-.69 0-1.153-.462T3 19.385V4.615q0-.69.463-1.152T4.615 3H12.5L17 7.5v5.039h-2.962V21zM12 8h4l-4-4zM5.962 18.23h8.077q-.081-.993-.597-1.816q-.515-.824-1.373-1.308l.758-1.373q.05-.081.015-.177q-.034-.096-.12-.146q-.082-.05-.165-.026t-.134.106l-.783 1.404q-.384-.161-.798-.245q-.413-.083-.842-.083t-.833.083t-.808.245l-.782-1.404q-.05-.086-.143-.106q-.094-.019-.18.031q-.02 0-.081.318l.777 1.373q-.858.485-1.383 1.308t-.606 1.817m1.948-1.333q-.12-.121-.12-.283t.12-.282t.283-.121t.273.12t.112.284q0 .161-.112.282q-.111.121-.273.121t-.283-.121m3.635 0q-.121-.121-.121-.283t.121-.282t.283-.121t.282.12t.122.284t-.122.282q-.12.121-.282.121t-.283-.121");
}

</style>
