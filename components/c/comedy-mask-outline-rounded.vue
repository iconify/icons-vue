<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tihmfrbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comedy-mask-outline-rounded" /></template>
<style>
.tihmfrbgt {
  fill: currentColor;
  d: path("M13.968 15.621q.853-.667 1.174-1.694q.07-.211-.061-.367t-.352-.156H9.254q-.212 0-.338.153q-.128.152-.078.37q.322 1.027 1.184 1.694q.863.667 1.978.667t1.968-.667M12.001 21q-1.664 0-3.12-.636q-1.454-.635-2.541-1.723T4.626 16.08T4 12.942V4.616q0-.667.475-1.141T5.615 3h12.77q.666 0 1.14.475T20 4.615v8.327q0 1.664-.626 3.138t-1.714 2.56t-2.54 1.724T12 21m-.01-1q2.909 0 4.959-2.06T19 12.942V4.615q0-.269-.173-.442T18.385 4H5.615q-.269 0-.442.173T5 4.616v8.326q0 2.939 2.04 4.999T11.99 20M8.208 7.958q-.426.323-.57.825q-.054.188.067.337t.344.15h2.265q.202 0 .333-.152t.081-.334q-.162-.503-.588-.826q-.426-.324-.966-.324t-.966.324m5.646 0q-.414.325-.575.811q-.06.183.06.332q.122.149.345.149h2.265q.202 0 .323-.151q.121-.152.071-.334q-.16-.484-.574-.807t-.957-.324t-.958.325");
}

</style>
