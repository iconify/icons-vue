<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk_tiz-xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:karaoke-mic-off" /></template>
<style>
.fk_tiz-xc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.664 10.627q.213-.157.406-.337t.363-.381q.171-.201.317-.421t.265-.456t.21-.483t.152-.504t.092-.519T16.5 7q0-.11-.005-.221q-.006-.11-.017-.22q-.01-.11-.027-.219q-.016-.11-.037-.218q-.022-.108-.049-.215q-.027-.108-.059-.213q-.032-.106-.069-.21t-.08-.206t-.089-.202t-.099-.197t-.109-.192t-.118-.187t-.128-.181t-.135-.174t-.145-.167q-.074-.082-.152-.16t-.16-.152t-.167-.145q-.086-.07-.174-.135q-.089-.066-.181-.128q-.092-.061-.187-.118q-.094-.057-.192-.109q-.097-.052-.197-.099t-.202-.089q-.102-.043-.206-.08t-.21-.069q-.105-.032-.213-.059q-.107-.027-.215-.049q-.108-.021-.218-.037q-.109-.017-.219-.027q-.11-.011-.22-.017Q12.11 2.5 12 2.5q-.268 0-.534.032t-.526.095t-.511.156t-.489.216t-.46.273t-.425.325q-.202.176-.383.374q-.18.198-.336.416m1.299 9.189L10.5 20.5h3l.338-2.701M3.5 3.5l17 17");
}

</style>
